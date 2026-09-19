<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za30a2l0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="za30a2l0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:dot" /></template>
