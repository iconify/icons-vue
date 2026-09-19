<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdxmgm20z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="kdxmgm20z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-sm-fill-12" /></template>
