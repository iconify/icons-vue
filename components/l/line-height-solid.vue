<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_sgg3b3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_sgg3b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:line-height-solid" /></template>
