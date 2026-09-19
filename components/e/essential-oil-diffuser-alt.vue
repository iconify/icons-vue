<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh070wbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh070wbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:essential-oil-diffuser-alt" /></template>
