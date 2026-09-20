<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns_i8fmkj.css';
import '../../css/c/cypjnfb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ns_i8fmkj"/><path class="cypjnfb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:lock" /></template>
