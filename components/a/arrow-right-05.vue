<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnx5eo-_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnx5eo-_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-right-05" /></template>
