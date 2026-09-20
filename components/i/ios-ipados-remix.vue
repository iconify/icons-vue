<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvbw6otav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xvbw6otav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ios-ipados-remix" /></template>
