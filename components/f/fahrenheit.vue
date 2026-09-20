<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5seh0bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5seh0bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:fahrenheit" /></template>
