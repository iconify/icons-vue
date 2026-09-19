<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq_lh9b1r.css';
import '../../css/z/z2r6h84kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kq_lh9b1r"/><path class="z2r6h84kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:files-empty" /></template>
