<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a54w-8bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a54w-8bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:android-solid" /></template>
