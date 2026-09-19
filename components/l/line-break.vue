<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dql26ryfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dql26ryfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:line-break" /></template>
