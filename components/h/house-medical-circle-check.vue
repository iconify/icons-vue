<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lypw1fb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="lypw1fb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:house-medical-circle-check" /></template>
