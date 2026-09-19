<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et7yk-bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="et7yk-bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:highlights" /></template>
