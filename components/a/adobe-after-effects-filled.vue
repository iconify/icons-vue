<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg2_fzpty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lg2_fzpty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:adobe-after-effects-filled" /></template>
