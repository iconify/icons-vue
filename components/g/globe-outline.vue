<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hof09nbzk.css';
import '../../css/t/t42cy5box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hof09nbzk"/><path clip-rule="evenodd" class="t42cy5box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:globe-outline" /></template>
