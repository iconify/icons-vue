<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnnf_6h8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnnf_6h8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bulma" /></template>
