<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvfwx8oct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvfwx8oct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gallery-view" /></template>
