<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzj2zq6ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="gzj2zq6ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:firewall" /></template>
