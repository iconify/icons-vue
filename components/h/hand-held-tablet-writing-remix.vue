<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6ew_ob-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z6ew_ob-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hand-held-tablet-writing-remix" /></template>
