<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm-td8bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hm-td8bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:keyboard-virtual-remix" /></template>
