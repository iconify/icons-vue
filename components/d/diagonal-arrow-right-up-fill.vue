<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfuo3_qvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfuo3_qvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:diagonal-arrow-right-up-fill" /></template>
