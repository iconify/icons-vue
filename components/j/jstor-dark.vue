<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br3r0diof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="br3r0diof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jstor-dark" /></template>
