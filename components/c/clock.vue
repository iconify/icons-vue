<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqj_zryfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqj_zryfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:clock" /></template>
