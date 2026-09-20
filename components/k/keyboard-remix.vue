<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib3aw7l4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ib3aw7l4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:keyboard-remix" /></template>
