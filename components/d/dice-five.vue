<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvt8df90n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xvt8df90n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:dice-five" /></template>
