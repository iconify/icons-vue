<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/i/i4it1pzvk.css';
import '../../css/t/t218te2ox.css';
import '../../css/e/ezx00wbry.css';
import '../../css/y/ytq6kubqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="i4it1pzvk wm-deco"/><path class="t218te2ox wm-deco"/><path class="ezx00wbry wm-k"/><path class="wm-a ytq6kubqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:address-book-blueprint" /></template>
