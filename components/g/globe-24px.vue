<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2dw2dclf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p2dw2dclf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:globe-24px" /></template>
