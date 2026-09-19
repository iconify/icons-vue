<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bct1xkbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bct1xkbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:dessert" /></template>
