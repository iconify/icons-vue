<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f57b36_hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f57b36_hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:database-minus" /></template>
