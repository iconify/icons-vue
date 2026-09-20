<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu0s5dbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mu0s5dbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:edit-crop" /></template>
