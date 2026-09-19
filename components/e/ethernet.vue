<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psz3s1eih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="psz3s1eih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:ethernet" /></template>
