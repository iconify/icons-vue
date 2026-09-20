<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlld-vbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vlld-vbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:database-subtract-1-remix" /></template>
