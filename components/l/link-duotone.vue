<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmdtu9bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmdtu9bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:link-duotone" /></template>
