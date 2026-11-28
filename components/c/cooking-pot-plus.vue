<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js098mbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js098mbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cooking-pot-plus" /></template>
