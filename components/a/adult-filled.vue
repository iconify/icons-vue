<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gna62mbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gna62mbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:adult-filled" /></template>
