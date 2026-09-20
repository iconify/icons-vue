<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx2j0nbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx2j0nbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chainguard" /></template>
