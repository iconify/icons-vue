<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akt89zb7w.css';
import '../../css/j/jleau3b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="akt89zb7w"/><path class="jleau3b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:document" /></template>
