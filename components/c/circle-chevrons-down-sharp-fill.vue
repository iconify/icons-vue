<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svc3u7xlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svc3u7xlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevrons-down-sharp-fill" /></template>
