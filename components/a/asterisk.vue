<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3o6v3kfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a3o6v3kfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:asterisk" /></template>
