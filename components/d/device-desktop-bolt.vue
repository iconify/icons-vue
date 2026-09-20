<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2m50rcmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2m50rcmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-desktop-bolt" /></template>
