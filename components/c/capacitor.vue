<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef1d_0bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef1d_0bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:capacitor" /></template>
