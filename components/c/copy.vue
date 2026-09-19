<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ughq2cbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ughq2cbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:copy" /></template>
