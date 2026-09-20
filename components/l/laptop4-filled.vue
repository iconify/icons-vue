<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx1e8bcvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nx1e8bcvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:laptop4-filled" /></template>
