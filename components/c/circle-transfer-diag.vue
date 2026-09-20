<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p40sy6z0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p40sy6z0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-transfer-diag" /></template>
