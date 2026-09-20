<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usnspjbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="usnspjbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:hospital-filled" /></template>
