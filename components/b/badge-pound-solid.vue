<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_uso5j8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_uso5j8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-pound-solid" /></template>
