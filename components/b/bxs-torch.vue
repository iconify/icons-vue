<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7ddl071r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7ddl071r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-torch" /></template>
