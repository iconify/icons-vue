<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeh9i_3ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeh9i_3ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask-round-bottom-empty-outline" /></template>
