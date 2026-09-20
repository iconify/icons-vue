<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yup-t7bvl.css';
import '../../css/m/m0sn3w28b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yup-t7bvl"/><path class="m0sn3w28b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hister-light" /></template>
