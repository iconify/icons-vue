<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upt28hb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="upt28hb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:like-1-solid" /></template>
