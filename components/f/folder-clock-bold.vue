<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxghssbvs.css';
import '../../css/q/ql_va_b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxghssbvs"/><path clip-rule="evenodd" class="ql_va_b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-clock-bold" /></template>
