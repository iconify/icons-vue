<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbsktt95j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cbsktt95j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:config-react" /></template>
