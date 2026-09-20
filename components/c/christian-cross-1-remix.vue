<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz8scw1xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sz8scw1xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:christian-cross-1-remix" /></template>
