<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu-95fbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nu-95fbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:fluxcd-wordmark" /></template>
