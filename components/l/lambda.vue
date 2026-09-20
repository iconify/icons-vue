<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aekmdbhix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aekmdbhix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lambda" /></template>
