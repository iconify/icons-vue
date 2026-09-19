<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl-50nbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yl-50nbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:ejectsymbol" /></template>
