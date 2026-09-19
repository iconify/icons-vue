<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpsarxbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="xpsarxbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:braillethree" /></template>
