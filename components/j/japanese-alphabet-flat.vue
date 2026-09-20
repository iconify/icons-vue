<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qho3rrbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qho3rrbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:japanese-alphabet-flat" /></template>
