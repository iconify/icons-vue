<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saeo7x0bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="saeo7x0bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:browser" /></template>
