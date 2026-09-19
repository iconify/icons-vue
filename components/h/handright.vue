<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trcjn3b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":704};
const content = `<path class="trcjn3b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:handright" /></template>
