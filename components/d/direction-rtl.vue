<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd4a16fbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="gd4a16fbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:direction-rtl" /></template>
