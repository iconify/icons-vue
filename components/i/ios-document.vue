<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blhdngppl.css';
import '../../css/c/cnc6799tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="blhdngppl"/><path class="cnc6799tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-document" /></template>
