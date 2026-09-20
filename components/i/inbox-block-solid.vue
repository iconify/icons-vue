<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymftsyb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ymftsyb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:inbox-block-solid" /></template>
