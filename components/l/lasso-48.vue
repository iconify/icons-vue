<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-7g8zgze.css';
import '../../css/c/ca_dbzwra.css';
import '../../css/e/evhwq2bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c-7g8zgze"/><path class="ca_dbzwra"/><path class="evhwq2bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lasso-48" /></template>
