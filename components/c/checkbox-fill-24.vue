<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kogph_qlv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kogph_qlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:checkbox-fill-24" /></template>
