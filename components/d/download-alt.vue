<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df37-cbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="df37-cbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:download-alt" /></template>
