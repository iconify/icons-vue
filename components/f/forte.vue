<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p17ncey3b.css';
import '../../css/s/s5j8cpt3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p17ncey3b"/><path class="s5j8cpt3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:forte" /></template>
