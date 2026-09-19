<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi_lh7bxp.css';
import '../../css/l/lu06jwoxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xi_lh7bxp"/><path class="lu06jwoxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:bbc" /></template>
