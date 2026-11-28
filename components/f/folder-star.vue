<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r57lnacnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r57lnacnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folder-star" /></template>
