<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-sd27hth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="x-sd27hth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:angle-dobule-left" /></template>
