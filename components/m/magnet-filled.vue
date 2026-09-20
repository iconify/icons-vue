<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddmyanztt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddmyanztt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:magnet-filled" /></template>
