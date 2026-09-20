<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_7m0i8by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_7m0i8by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:almalinux" /></template>
