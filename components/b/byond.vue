<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf2q0k68c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pf2q0k68c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:byond" /></template>
