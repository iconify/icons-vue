<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqe-nepgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqe-nepgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:beer" /></template>
