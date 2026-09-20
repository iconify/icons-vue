<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or_f8oh-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or_f8oh-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cycling-74" /></template>
