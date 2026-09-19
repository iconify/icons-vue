<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2a_qteud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="g2a_qteud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:diagnoses" /></template>
