<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj96adbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj96adbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:book-open" /></template>
