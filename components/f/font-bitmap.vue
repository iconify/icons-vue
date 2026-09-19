<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3__s4b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t3__s4b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:font-bitmap" /></template>
