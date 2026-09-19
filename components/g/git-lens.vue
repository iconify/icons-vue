<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzdcv_boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzdcv_boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:git-lens" /></template>
