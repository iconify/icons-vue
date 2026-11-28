<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irrxlab0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irrxlab0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clock" /></template>
