<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf_g46bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf_g46bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:banknote-minus" /></template>
