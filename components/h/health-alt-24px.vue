<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfx6z8-hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nfx6z8-hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:health-alt-24px" /></template>
