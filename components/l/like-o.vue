<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwy9vrrqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gwy9vrrqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:like-o" /></template>
