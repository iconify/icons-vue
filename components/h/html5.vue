<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbs6rebdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pbs6rebdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:html5" /></template>
