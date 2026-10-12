<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2d9xbigc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2d9xbigc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:fold-vertical" /></template>
