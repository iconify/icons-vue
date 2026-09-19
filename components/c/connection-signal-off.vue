<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on0krzm9t.css';
import '../../css/w/wdxgscteg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="on0krzm9t"/><path class="wdxgscteg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:connection-signal-off" /></template>
