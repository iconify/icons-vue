<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phz_w4bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phz_w4bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:layout-grid-small" /></template>
