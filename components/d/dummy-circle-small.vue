<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7ivh0b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7ivh0b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:dummy-circle-small" /></template>
