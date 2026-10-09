<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwpdu4b2p.css';
import '../../css/x/xfd9_p-un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cwpdu4b2p"/><path class="xfd9_p-un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ladle-20" /></template>
