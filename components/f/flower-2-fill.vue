<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahyghgztp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahyghgztp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flower-2-fill" /></template>
