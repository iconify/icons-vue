<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gox7g7b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="gox7g7b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-holding-medical" /></template>
