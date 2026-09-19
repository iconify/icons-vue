<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xick6v_8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xick6v_8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bad-one" /></template>
