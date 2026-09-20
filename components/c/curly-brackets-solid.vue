<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss2me_b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ss2me_b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:curly-brackets-solid" /></template>
