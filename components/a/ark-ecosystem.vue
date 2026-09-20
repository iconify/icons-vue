<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd720b16h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd720b16h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ark-ecosystem" /></template>
