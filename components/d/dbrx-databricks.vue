<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_v22q00v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_v22q00v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dbrx-databricks" /></template>
