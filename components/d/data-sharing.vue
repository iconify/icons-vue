<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn5_oubwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn5_oubwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:data-sharing" /></template>
