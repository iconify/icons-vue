<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqr5l8bbj.css';
import '../../css/g/gp7kg8iqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="eqr5l8bbj"/><path class="gp7kg8iqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:diver-down" /></template>
