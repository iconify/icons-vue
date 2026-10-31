<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy17h1biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qy17h1biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrows-crossing-solid" /></template>
