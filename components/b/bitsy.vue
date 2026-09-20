<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsx06-b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsx06-b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bitsy" /></template>
