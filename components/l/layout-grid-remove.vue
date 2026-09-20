<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3tnx-bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3tnx-bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-grid-remove" /></template>
