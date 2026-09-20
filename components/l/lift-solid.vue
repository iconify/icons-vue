<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y680uoblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y680uoblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:lift-solid" /></template>
