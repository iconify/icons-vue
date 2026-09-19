<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-e1deksh.css';
import '../../css/d/dzrwv9dgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n-e1deksh"/><path class="dzrwv9dgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:copy" /></template>
