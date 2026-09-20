<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgmse4pkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jgmse4pkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:disney-plus-light" /></template>
