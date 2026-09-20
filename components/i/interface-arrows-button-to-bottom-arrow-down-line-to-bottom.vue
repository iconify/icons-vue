<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi28l3syr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bi28l3syr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-button-to-bottom-arrow-down-line-to-bottom" /></template>
