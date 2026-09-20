<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj9rp95rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj9rp95rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:flightaware" /></template>
