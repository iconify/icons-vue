<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1wx11b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f1wx11b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:iconjar" /></template>
