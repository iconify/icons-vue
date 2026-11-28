<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7resrb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7resrb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:files-x" /></template>
