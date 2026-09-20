<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph9k6dtye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ph9k6dtye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-left2-filled" /></template>
