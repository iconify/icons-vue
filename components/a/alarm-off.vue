<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb0kjw99d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440,"height":432};
const content = `<path class="fb0kjw99d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:alarm-off" /></template>
