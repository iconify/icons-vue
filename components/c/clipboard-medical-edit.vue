<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3rpl4bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3rpl4bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clipboard-medical-edit" /></template>
