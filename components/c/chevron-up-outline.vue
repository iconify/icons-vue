<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvjcoub6v.css';
import '../../css/e/efsylsb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gvjcoub6v"/><path class="efsylsb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chevron-up-outline" /></template>
