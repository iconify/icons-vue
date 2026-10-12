<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfu_5sb2s.css';
import '../../css/z/zu9il-bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sfu_5sb2s"/><path class="zu9il-bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:graduate-cap-fill-20" /></template>
