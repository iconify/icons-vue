<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v59xqacos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="v59xqacos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fatarrowleft" /></template>
