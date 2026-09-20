<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6yug67vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6yug67vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-contract-dollar" /></template>
