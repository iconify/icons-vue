<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbjb7acud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbjb7acud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:camping-filled" /></template>
