<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0as2hbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l0as2hbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:edit-pen" /></template>
