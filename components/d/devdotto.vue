<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-qc9d92w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-qc9d92w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:devdotto" /></template>
