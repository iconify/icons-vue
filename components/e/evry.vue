<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fde_ztj2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fde_ztj2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:evry" /></template>
