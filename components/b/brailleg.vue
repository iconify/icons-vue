<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb9313biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="vb9313biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brailleg" /></template>
