<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lae-utkpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="lae-utkpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:k-upper-case" /></template>
