<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky693gb4a.css';
import '../../css/m/mkb2ul-2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ky693gb4a"/><path class="mkb2ul-2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hex-nut-20" /></template>
