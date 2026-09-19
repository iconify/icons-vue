<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn1vx7i1f.css';
import '../../css/b/bfpgpzbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vn1vx7i1f"/><path class="bfpgpzbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bookmarks" /></template>
