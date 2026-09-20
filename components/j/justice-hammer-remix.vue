<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smezn0u9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="smezn0u9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:justice-hammer-remix" /></template>
