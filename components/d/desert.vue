<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi_p0qsvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi_p0qsvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:desert" /></template>
