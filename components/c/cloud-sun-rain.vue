<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dco9n2bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dco9n2bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-sun-rain" /></template>
