<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d60h96b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d60h96b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:login" /></template>
