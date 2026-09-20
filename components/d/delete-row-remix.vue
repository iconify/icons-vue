<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_-d0tb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x_-d0tb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:delete-row-remix" /></template>
