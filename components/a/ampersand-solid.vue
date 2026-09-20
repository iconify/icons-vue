<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lin6cdbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lin6cdbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ampersand-solid" /></template>
