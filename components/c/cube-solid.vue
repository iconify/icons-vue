<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uykcr3bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uykcr3bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cube-solid" /></template>
