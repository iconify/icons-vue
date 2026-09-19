<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyh6w9b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vyh6w9b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:block-one" /></template>
