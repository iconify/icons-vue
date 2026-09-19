<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqsmbj5lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqsmbj5lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:file-export" /></template>
