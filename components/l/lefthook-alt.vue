<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbf3x-bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kbf3x-bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lefthook-alt" /></template>
