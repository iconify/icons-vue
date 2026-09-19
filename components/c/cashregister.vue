<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whc-d3s-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="whc-d3s-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cashregister" /></template>
