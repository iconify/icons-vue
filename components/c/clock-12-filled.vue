<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttpet3brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ttpet3brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clock-12-filled" /></template>
