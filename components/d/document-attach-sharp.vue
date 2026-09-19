<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-zsa5bjg.css';
import '../../css/j/j0-b_gamb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c-zsa5bjg"/><path class="j0-b_gamb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:document-attach-sharp" /></template>
