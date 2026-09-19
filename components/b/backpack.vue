<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l72lr_b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l72lr_b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:backpack" /></template>
