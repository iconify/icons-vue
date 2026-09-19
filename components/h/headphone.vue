<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa2a3yo4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa2a3yo4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:headphone" /></template>
