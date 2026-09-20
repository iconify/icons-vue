<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/e/e9-zai.css';
import '../../css/d/dm-51m.css';
import '../../css/c/c-b7rz.css';
import '../../css/n/ndxadb.css';
import '../../css/s/so-from-30.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d-ll345f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c e9-zai"/><path class="a0m25c dm-51m"/><path class="a0m25c c-b7rz"/><path class="ndxadb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cake" /></template>
