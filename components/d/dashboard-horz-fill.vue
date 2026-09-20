<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-8258b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-8258b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:dashboard-horz-fill" /></template>
