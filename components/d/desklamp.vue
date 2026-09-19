<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b691pxbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="b691pxbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:desklamp" /></template>
