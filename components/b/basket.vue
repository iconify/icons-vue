<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pydz04b8f.css';
import '../../css/o/ockmixada.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pydz04b8f"/><path class="ockmixada"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:basket" /></template>
