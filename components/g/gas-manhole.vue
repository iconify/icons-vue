<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl5jfab4x.css';
import '../../css/n/n_4tgoa7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dl5jfab4x"/><path class="n_4tgoa7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:gas-manhole" /></template>
