<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dae8fsb4j.css';
import '../../css/e/e3_9xhb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dae8fsb4j"/><path class="e3_9xhb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:education-filled" /></template>
