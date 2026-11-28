<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty_q0zb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty_q0zb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:film-pause" /></template>
