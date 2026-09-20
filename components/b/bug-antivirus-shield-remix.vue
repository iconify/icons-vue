<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqlaruk5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qqlaruk5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:bug-antivirus-shield-remix" /></template>
