<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9o_4nb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9o_4nb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:goblet-broken-fill" /></template>
