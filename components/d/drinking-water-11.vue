<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh_sznb5z.css';
import '../../css/z/zz6yhdbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="kh_sznb5z"/><path class="zz6yhdbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:drinking-water-11" /></template>
