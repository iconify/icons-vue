<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om1j0hb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om1j0hb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:coffee-outline" /></template>
