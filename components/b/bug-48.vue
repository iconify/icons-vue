<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da3bf5bbj.css';
import '../../css/g/gtz69mu0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="da3bf5bbj"/><path class="gtz69mu0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bug-48" /></template>
