<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-0l1ebhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-0l1ebhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:eyedropper-filled" /></template>
