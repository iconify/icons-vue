<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc7beos3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pc7beos3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:finger-snapping-remix" /></template>
