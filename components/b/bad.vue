<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spvo8abkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="spvo8abkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:bad" /></template>
