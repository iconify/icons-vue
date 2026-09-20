<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn7nyeb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn7nyeb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:cobalt" /></template>
