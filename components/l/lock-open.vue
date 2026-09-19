<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzfmp9irn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzfmp9irn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:lock-open" /></template>
