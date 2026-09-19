<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y--ket0br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="y--ket0br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:eye" /></template>
