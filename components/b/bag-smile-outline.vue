<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp4pd42li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qp4pd42li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-smile-outline" /></template>
