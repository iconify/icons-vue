<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgs0-ho5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgs0-ho5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:groceries-filled" /></template>
