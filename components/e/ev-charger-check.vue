<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcq30tebd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcq30tebd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ev-charger-check" /></template>
