<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0ul-uz9o.css';
import '../../css/o/oc7c-mb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e0ul-uz9o"/><path class="oc7c-mb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:alarm" /></template>
