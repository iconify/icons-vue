<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3erhq7-p.css';
import '../../css/m/m5_1mibrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y3erhq7-p"/><path clip-rule="evenodd" class="m5_1mibrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:eye-16" /></template>
