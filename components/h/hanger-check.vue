<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebw6zj4kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebw6zj4kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hanger-check" /></template>
