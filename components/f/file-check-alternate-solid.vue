<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4bs_w5rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l4bs_w5rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:file-check-alternate-solid" /></template>
