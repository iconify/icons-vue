<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvqi0v3hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvqi0v3hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bell" /></template>
