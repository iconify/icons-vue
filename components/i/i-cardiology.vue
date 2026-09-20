<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms1ycbcfl.css';
import '../../css/l/ln5q-fheg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ms1ycbcfl"/><path class="ln5q-fheg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-cardiology" /></template>
