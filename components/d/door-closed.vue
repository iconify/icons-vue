<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jarabnk1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="jarabnk1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:door-closed" /></template>
