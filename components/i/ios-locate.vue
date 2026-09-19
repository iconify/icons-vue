<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwlq_8b3i.css';
import '../../css/r/roy4gvbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uwlq_8b3i"/><path class="roy4gvbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-locate" /></template>
