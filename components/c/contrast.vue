<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teyd1mnlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="teyd1mnlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:contrast" /></template>
