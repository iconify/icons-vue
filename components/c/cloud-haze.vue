<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyp7lccqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wyp7lccqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-haze" /></template>
