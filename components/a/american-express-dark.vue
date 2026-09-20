<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0m-u9b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z0m-u9b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:american-express-dark" /></template>
