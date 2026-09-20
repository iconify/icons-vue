<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dovo1zbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dovo1zbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-cancel" /></template>
