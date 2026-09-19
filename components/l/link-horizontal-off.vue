<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcmm31bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcmm31bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:link-horizontal-off" /></template>
