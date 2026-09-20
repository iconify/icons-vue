<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqoj9abcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqoj9abcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:burger-king" /></template>
