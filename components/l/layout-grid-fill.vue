<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0rxg3blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0rxg3blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:layout-grid-fill" /></template>
