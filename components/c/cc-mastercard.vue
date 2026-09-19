<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcafiqwep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zcafiqwep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:cc-mastercard" /></template>
