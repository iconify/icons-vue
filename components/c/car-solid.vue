<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br4kg7krz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="br4kg7krz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:car-solid" /></template>
