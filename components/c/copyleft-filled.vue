<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_5gqc-yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_5gqc-yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:copyleft-filled" /></template>
