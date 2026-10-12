<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzlce4mmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mzlce4mmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:emoji-sad-fill-20" /></template>
