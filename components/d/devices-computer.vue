<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tny4sibjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tny4sibjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:devices-computer" /></template>
