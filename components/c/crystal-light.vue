<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7qd0xhrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":200,"height":200};
const content = `<path class="k7qd0xhrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:crystal-light" /></template>
