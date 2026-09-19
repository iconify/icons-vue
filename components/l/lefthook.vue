<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-i-v1v3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m-i-v1v3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lefthook" /></template>
