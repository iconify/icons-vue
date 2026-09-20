<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9_mgebnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e9_mgebnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:address-card-filled" /></template>
