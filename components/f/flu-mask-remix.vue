<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vni83uqvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vni83uqvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flu-mask-remix" /></template>
