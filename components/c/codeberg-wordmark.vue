<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgf_ijbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bgf_ijbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:codeberg-wordmark" /></template>
