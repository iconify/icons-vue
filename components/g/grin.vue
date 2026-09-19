<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmxm2bcmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hmxm2bcmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:grin" /></template>
