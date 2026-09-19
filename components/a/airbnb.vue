<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqk-lo6pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zqk-lo6pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:airbnb" /></template>
