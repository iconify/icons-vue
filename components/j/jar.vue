<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1t180kcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="u1t180kcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:jar" /></template>
