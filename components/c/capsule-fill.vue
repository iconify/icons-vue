<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqrfsh1mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqrfsh1mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:capsule-fill" /></template>
