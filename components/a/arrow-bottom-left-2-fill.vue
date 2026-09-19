<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o34222bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o34222bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-left-2-fill" /></template>
