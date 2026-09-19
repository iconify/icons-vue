<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf86pn3hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jf86pn3hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:facebook-messenger" /></template>
