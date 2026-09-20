<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7lr2mkyr.css';
import '../../css/h/hhhhlk_ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j7lr2mkyr"/><path class="hhhhlk_ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:church-solid" /></template>
