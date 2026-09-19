<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3hiveb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u3hiveb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:fire-two" /></template>
