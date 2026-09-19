<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daw-5ibwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="daw-5ibwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:alienware" /></template>
