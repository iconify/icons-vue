<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqik6r9ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqik6r9ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:circle-right" /></template>
