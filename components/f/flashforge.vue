<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj6jh_bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj6jh_bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:flashforge" /></template>
