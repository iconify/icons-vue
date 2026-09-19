<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk9y8_tpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="pk9y8_tpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:lines-leaning" /></template>
