<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo_x6wbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wo_x6wbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:config-haskell" /></template>
