<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp1jkewkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp1jkewkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fold-horizontal-line" /></template>
