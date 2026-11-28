<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmdz2cboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmdz2cboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-diamond-solid" /></template>
