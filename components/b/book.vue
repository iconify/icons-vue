<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gngoa7gvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="gngoa7gvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:book" /></template>
