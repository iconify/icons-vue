<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp-6wrbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":288,"height":512};
const content = `<path class="cp-6wrbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:genderless" /></template>
