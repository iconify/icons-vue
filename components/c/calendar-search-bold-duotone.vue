<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm_gscbzc.css';
import '../../css/j/j6xrxv6-w.css';
import '../../css/z/zw-s4mi4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wm_gscbzc"/><path class="j6xrxv6-w"/><path class="zw-s4mi4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-search-bold-duotone" /></template>
