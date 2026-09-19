<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9mu7dbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":488,"height":512};
const content = `<path class="g9mu7dbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:flag-corner" /></template>
