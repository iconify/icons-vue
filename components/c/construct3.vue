<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh_b1tqjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh_b1tqjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:construct3" /></template>
