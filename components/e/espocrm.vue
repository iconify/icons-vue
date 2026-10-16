<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe1t213fe.css';
import '../../css/o/o3xf0rsxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8.467,"height":8.467};
const content = `<circle class="fe1t213fe"/><path class="o3xf0rsxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:espocrm" /></template>
