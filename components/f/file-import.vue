<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-m10qbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-m10qbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-import" /></template>
