<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-w7pwb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="o-w7pwb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bamboo" /></template>
