<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksz2pjk8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ksz2pjk8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:inform7" /></template>
