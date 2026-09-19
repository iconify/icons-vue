<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olsexebsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="olsexebsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:exchange-four" /></template>
