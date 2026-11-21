<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8i9flbaf.css';
import '../../css/n/njfu2s7nv.css';
import '../../css/o/ow0ge3umc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8i9flbaf"/><path class="njfu2s7nv"/><path class="ow0ge3umc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layers-arrow-up-filled" /></template>
