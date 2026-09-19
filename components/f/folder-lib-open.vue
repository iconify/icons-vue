<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i12ji_bzg.css';
import '../../css/l/lyimn3yqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i12ji_bzg"/><path class="lyimn3yqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-lib-open" /></template>
