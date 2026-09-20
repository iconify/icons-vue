<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqfa2vbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqfa2vbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-t-waves-solid" /></template>
