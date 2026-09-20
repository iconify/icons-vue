<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn_3m2b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kn_3m2b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cog" /></template>
