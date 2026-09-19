<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zshm6db-x.css';
import '../../css/v/v9nm23b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zshm6db-x"/><circle class="v9nm23b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:golf" /></template>
