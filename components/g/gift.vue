<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t29596blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t29596blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gift" /></template>
