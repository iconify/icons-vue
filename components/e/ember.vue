<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn4yg_1oe.css';
import '../../css/l/lsp0zwf3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sn4yg_1oe"/><path class="lsp0zwf3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ember" /></template>
