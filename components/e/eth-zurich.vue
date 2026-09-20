<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr14q2brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":331};
const content = `<path class="kr14q2brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:eth-zurich" /></template>
