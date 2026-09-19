<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw4ax2p7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kw4ax2p7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:freecodecamp" /></template>
