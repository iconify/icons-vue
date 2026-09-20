<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf4b16pqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wf4b16pqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:earbuds-right" /></template>
