<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogx8amvsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ogx8amvsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:attention-circle-fill" /></template>
