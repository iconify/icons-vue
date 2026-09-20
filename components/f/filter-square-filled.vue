<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6yl7xz3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6yl7xz3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:filter-square-filled" /></template>
