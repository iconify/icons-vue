<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqqmgdcri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqqmgdcri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:export2" /></template>
