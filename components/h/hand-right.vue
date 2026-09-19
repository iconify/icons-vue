<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-56etbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="b-56etbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:hand-right" /></template>
