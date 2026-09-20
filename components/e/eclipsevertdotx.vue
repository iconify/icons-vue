<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-f6te6sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-f6te6sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:eclipsevertdotx" /></template>
