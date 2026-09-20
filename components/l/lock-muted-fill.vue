<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw4wzobeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uw4wzobeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:lock-muted-fill" /></template>
