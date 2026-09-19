<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uayhwehie.css';
import '../../css/b/bm73ro2ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uayhwehie"/><path class="bm73ro2ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bookmarks" /></template>
