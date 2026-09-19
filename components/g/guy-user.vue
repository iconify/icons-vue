<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggh7wdatt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":328,"height":512};
const content = `<path class="ggh7wdatt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:guy-user" /></template>
