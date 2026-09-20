<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7rms6bun.css';
import '../../css/p/pnnc77hwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7rms6bun"/><path class="pnnc77hwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-multiple-solid" /></template>
