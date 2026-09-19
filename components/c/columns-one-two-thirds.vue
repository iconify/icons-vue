<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6t11bbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6t11bbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:columns-one-two-thirds" /></template>
