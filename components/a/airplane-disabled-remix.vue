<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3bo38t3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b3bo38t3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:airplane-disabled-remix" /></template>
