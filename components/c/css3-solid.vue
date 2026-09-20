<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s46uwy_pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="s46uwy_pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:css3-solid" /></template>
