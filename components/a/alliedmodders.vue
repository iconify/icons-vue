<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdk1bkb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdk1bkb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:alliedmodders" /></template>
