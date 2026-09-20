<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw8y06qco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw8y06qco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-summarize-alt-fill" /></template>
