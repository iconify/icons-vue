<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu376izwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu376izwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrow-random" /></template>
