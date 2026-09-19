<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwv6sm2lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qwv6sm2lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:font-outline" /></template>
