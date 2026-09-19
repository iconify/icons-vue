<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bihu32bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bihu32bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lifesaver-fill-16" /></template>
