<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_r1k3bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_r1k3bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apache-doris" /></template>
