<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f876vrb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f876vrb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cookie-alert" /></template>
