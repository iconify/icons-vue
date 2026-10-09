<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw78uccpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pw78uccpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-up-48" /></template>
