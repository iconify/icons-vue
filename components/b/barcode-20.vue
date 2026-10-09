<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuxhki93l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kuxhki93l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:barcode-20" /></template>
