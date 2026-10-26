<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coj7f6n0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":220.61,"height":173.65};
const content = `<path class="coj7f6n0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:karmada" /></template>
