<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbo5oob-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="fbo5oob-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:cc-diners-club" /></template>
