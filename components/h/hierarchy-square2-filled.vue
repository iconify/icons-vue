<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwg9x0t8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwg9x0t8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hierarchy-square2-filled" /></template>
