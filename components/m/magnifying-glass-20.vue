<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwv90_00a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nwv90_00a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:magnifying-glass-20" /></template>
