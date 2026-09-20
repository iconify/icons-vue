<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdryfmbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdryfmbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-k-circle-solid" /></template>
