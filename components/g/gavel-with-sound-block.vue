<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k68etbpof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k68etbpof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gavel-with-sound-block" /></template>
