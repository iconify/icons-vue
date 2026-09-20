<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpf5-09ok.css';
import '../../css/h/hpmvmqb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="wpf5-09ok"/><path class="hpmvmqb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-search-filled" /></template>
