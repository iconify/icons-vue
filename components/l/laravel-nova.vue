<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf_qqhb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf_qqhb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:laravel-nova" /></template>
