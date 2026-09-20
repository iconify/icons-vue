<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq4k6swtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq4k6swtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:issues-reopen-fill" /></template>
