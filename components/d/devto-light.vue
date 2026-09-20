<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-2ge42fi.css';
import '../../css/l/llfj4f_hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="e-2ge42fi"/><path class="llfj4f_hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:devto-light" /></template>
