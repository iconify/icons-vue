<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs1be3nix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zs1be3nix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:h3" /></template>
