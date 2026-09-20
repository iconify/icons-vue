<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzq33dbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzq33dbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:corner-down-right-alt" /></template>
