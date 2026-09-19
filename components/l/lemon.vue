<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qix_boums.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qix_boums"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:lemon" /></template>
