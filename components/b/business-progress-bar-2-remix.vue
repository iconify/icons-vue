<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx8kvybnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fx8kvybnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:business-progress-bar-2-remix" /></template>
