<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd0sfqb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd0sfqb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bed" /></template>
