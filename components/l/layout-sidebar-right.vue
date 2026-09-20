<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pccf_ob1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pccf_ob1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:layout-sidebar-right" /></template>
