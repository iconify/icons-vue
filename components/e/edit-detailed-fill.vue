<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z44npe1px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z44npe1px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:edit-detailed-fill" /></template>
