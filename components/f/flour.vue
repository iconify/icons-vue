<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okq2mbbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="okq2mbbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flour" /></template>
