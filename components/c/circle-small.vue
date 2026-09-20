<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q26bobc_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="q26bobc_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:circle-small" /></template>
