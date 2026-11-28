<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn3q9eaqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn3q9eaqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-terminal-solid" /></template>
