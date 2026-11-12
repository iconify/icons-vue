<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu2v_2bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yu2v_2bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:composerize-dark" /></template>
