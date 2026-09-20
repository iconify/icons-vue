<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-t-g0bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t-t-g0bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:inbox-favorite-remix" /></template>
