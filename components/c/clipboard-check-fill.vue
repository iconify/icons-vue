<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqm1kybcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqm1kybcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clipboard-check-fill" /></template>
