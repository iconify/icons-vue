<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riq6uybqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="riq6uybqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:dice-6" /></template>
