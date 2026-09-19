<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2nqf8t8e.css';
import '../../css/v/vqb--ibgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n2nqf8t8e"/><path class="vqb--ibgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-closed-captioning" /></template>
