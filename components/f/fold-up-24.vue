<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-w3942xx.css';
import '../../css/c/csowzdbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-w3942xx"/><path class="csowzdbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:fold-up-24" /></template>
