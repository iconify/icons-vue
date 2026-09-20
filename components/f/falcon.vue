<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb_w47var.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb_w47var"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:falcon" /></template>
