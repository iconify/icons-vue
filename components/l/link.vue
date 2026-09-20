<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifk2jpbym.css';
import '../../css/d/danpsob9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ifk2jpbym"/><path class="danpsob9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:link" /></template>
