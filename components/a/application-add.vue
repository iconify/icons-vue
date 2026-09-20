<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc1xdqzrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xc1xdqzrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:application-add" /></template>
