<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cusxm9bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cusxm9bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:key2" /></template>
