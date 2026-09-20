<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xezfrunop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xezfrunop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:building-a-fill" /></template>
