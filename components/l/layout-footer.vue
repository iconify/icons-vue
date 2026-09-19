<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnl5jcclz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pnl5jcclz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:layout-footer" /></template>
