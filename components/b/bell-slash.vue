<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lacbqkb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1792};
const content = `<path class="lacbqkb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bell-slash" /></template>
