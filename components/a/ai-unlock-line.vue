<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltsz15pbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltsz15pbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-unlock-line" /></template>
