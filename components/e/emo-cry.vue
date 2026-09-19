<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo2ttybuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":851,"height":1000};
const content = `<path class="qo2ttybuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-cry" /></template>
