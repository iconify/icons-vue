<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_vmfnb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="f_vmfnb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bring-to-front" /></template>
