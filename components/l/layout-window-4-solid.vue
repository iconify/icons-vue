<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p47g3hbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p47g3hbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:layout-window-4-solid" /></template>
