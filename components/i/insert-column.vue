<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeu2khb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qeu2khb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:insert-column" /></template>
