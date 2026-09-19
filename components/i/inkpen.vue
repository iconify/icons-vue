<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo28_obpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="qo28_obpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:inkpen" /></template>
