<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqgu7wbdd.css';
import '../../css/f/f7k04-ada.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sqgu7wbdd"/><path clip-rule="evenodd" class="f7k04-ada"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:archive-solid" /></template>
