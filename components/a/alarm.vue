<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8__0mb4m.css';
import '../../css/b/bb_scruft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m8__0mb4m"/><path class="bb_scruft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:alarm" /></template>
