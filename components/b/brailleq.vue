<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxs6jfbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="fxs6jfbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brailleq" /></template>
