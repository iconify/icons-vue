<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmmn-y2cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xmmn-y2cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:globe-outline" /></template>
