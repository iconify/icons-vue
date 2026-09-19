<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyow3oocf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="kyow3oocf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:angle-dobule-right" /></template>
