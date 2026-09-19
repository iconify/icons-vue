<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdf4m1b4v.css';
import '../../css/e/e3rrscc8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="mdf4m1b4v"/><path class="e3rrscc8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:download" /></template>
