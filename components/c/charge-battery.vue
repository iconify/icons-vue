<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppuvh0l0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ppuvh0l0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:charge-battery" /></template>
