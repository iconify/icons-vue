<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbt7-c2ud.css';
import '../../css/s/sug610m-v.css';
import '../../css/g/gz0iumbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rbt7-c2ud"/><path class="sug610m-v"/><path class="gz0iumbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cocktail-48" /></template>
