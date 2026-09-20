<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln6cmdy5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ln6cmdy5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:blank-calendar-remix" /></template>
