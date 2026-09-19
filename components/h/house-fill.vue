<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl18htbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gl18htbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:house-fill" /></template>
