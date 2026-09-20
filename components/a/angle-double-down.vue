<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr43w4bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr43w4bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:angle-double-down" /></template>
