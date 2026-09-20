<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbn8drbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bbn8drbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bluetooth" /></template>
