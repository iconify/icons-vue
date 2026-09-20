<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf_adyava.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf_adyava"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:deno-deploy" /></template>
