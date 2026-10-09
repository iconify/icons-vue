<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcwdncb4h.css';
import '../../css/t/to1elzbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zcwdncb4h"/><path class="to1elzbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:link-20" /></template>
