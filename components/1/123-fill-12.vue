<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn7jf3uuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fn7jf3uuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:123-fill-12" /></template>
