<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txz6rnsnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="txz6rnsnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jamstack-wordmark" /></template>
