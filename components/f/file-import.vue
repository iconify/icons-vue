<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i32yzb5md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i32yzb5md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:file-import" /></template>
