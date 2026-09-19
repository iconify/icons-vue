<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxh8uybpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kxh8uybpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:goblet" /></template>
