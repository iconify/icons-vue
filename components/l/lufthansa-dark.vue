<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obj3babap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="obj3babap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lufthansa-dark" /></template>
