<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekt9y_bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ekt9y_bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:location-pin-minus" /></template>
