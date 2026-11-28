<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea5taoauh.css';
import '../../css/z/zel29wb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea5taoauh secondary"/><path class="primary zel29wb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:heart-duo" /></template>
