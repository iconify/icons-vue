<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt0wbq9gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt0wbq9gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cooker" /></template>
