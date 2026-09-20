<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz44edbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz44edbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cachyos" /></template>
