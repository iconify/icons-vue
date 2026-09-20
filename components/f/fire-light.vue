<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcmlopf1w.css';
import '../../css/n/nhd6537wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcmlopf1w"/><path class="nhd6537wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:fire-light" /></template>
