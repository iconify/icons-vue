<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbx4iobsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbx4iobsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-40" /></template>
