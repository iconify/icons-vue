<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nciinvb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nciinvb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crop-1-1" /></template>
