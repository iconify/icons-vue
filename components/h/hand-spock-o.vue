<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nst4do0bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1792};
const content = `<path class="nst4do0bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hand-spock-o" /></template>
