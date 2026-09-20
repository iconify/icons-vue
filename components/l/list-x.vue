<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8ir75bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8ir75bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-x" /></template>
