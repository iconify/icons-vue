<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5rqqw-vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5rqqw-vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-agent-solid" /></template>
