<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psgy_eb5i.css';
import '../../css/x/x-nm31bum.css';
import '../../css/u/u9z2pachv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="psgy_eb5i"/><path class="x-nm31bum"/><path class="u9z2pachv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ammonia-tank-20" /></template>
