<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvoizu5zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvoizu5zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-t-shirt" /></template>
