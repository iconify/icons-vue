<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbtulp5np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lbtulp5np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:exclamation-circle-solid" /></template>
