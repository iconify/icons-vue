<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zieuvnddo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zieuvnddo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:creative-commons-filled" /></template>
