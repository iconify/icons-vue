<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qykgvefws.css';
import '../../css/i/ixcmx5bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qykgvefws"/><path class="ixcmx5bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kwenta" /></template>
