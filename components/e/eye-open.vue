<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_9kv2fjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="b_9kv2fjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:eye-open" /></template>
