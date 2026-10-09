<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_xt6zhqo.css';
import '../../css/c/c1okp3bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l_xt6zhqo"/><path class="c1okp3bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:briefcase-48-bold" /></template>
