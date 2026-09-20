<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqt6xqifr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="jqt6xqifr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:logging-11" /></template>
