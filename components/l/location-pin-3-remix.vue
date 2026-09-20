<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx9azvbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xx9azvbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:location-pin-3-remix" /></template>
