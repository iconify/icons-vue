<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw884i5gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qw884i5gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:cell-formating-border-horizontal-vertical" /></template>
