<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akt37cc3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="akt37cc3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:back" /></template>
