<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljp-s5bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="ljp-s5bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:drmanhattan" /></template>
