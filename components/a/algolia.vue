<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sei1hna7r.css';
import '../../css/b/b2of3ebrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sei1hna7r"/><path class="b2of3ebrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:algolia" /></template>
