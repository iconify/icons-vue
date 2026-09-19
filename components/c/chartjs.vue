<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph619sbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":444,"height":512};
const content = `<path class="ph619sbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:chartjs" /></template>
