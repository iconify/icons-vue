<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glggx6o7t.css';
import '../../css/s/sj_1l9bqr.css';
import '../../css/l/lmf0ecbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="glggx6o7t"/><path class="sj_1l9bqr"/><circle class="lmf0ecbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:host-outline-badged" /></template>
