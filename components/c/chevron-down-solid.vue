<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_1ja2b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_1ja2b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-down-solid" /></template>
