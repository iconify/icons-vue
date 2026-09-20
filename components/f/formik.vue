<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_70_7k6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_70_7k6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:formik" /></template>
