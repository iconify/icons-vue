<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovfe7jkjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovfe7jkjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hexagon" /></template>
