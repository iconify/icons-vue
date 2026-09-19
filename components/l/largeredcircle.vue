<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myy2k-mkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="myy2k-mkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:largeredcircle" /></template>
