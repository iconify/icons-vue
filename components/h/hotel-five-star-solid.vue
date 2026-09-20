<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c85d7-bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="c85d7-bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:hotel-five-star-solid" /></template>
