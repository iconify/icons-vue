<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm-2r_bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hm-2r_bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-right-up" /></template>
