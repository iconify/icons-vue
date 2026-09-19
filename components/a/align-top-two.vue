<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm6zm16-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mm6zm16-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:align-top-two" /></template>
