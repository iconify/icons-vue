<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/digorjb9f.css';
import '../../css/q/qfy_7db_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="digorjb9f"/><path class="qfy_7db_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dgx" /></template>
