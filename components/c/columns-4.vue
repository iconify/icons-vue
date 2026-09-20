<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw2-p-bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw2-p-bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:columns-4" /></template>
