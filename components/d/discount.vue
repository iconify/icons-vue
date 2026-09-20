<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rao67hbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rao67hbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:discount" /></template>
