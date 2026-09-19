<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jliq_xbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jliq_xbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:comment" /></template>
