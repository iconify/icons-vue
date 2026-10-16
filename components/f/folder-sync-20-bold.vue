<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt8f-3eoh.css';
import '../../css/i/i0ed3gb6r.css';
import '../../css/i/ilel_r_ca.css';
import '../../css/s/stu8q3lpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dt8f-3eoh"/><path class="i0ed3gb6r"/><path class="ilel_r_ca"/><path class="stu8q3lpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-sync-20-bold" /></template>
