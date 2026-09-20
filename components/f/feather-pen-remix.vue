<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_8gb412d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f_8gb412d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:feather-pen-remix" /></template>
