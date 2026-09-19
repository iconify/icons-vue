<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6k7g-b_u.css';
import '../../css/p/pr5vy7b3b.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 r6k7g-b_u"/><path class="clr-i-solid clr-i-solid-path-2 pr5vy7b3b"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:hard-disk-solid" /></template>
