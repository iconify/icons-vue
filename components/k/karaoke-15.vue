<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xowwcxs5r.css';
import '../../css/i/is011gbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xowwcxs5r"/><path class="is011gbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:karaoke-15" /></template>
