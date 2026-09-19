<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxvrc-n9x.css';
import '../../css/w/wtfir1bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="fxvrc-n9x"/><path class="wtfir1bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:globe-shield" /></template>
