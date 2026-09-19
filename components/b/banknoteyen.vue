<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eebag5dgs.css';
import '../../css/v/vlmk0rb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eebag5dgs"/><path class="vlmk0rb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:banknoteyen" /></template>
