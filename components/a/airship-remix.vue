<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qujgu5bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qujgu5bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:airship-remix" /></template>
