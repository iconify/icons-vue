<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv1jh76rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv1jh76rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:dashboard" /></template>
