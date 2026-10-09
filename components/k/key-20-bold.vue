<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgdsozb-t.css';
import '../../css/s/scwdfi6dx.css';
import '../../css/p/pb060eflr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bgdsozb-t"/><path class="scwdfi6dx"/><path class="pb060eflr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:key-20-bold" /></template>
