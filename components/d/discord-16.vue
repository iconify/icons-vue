<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3j5tbb3r.css';
import '../../css/p/p1hlxdb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q3j5tbb3r"/><path clip-rule="evenodd" class="p1hlxdb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:discord-16" /></template>
