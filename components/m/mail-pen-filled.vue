<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy1isrbes.css';
import '../../css/z/zrmu6-ymm.css';
import '../../css/z/zc_h-6bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy1isrbes"/><path class="zrmu6-ymm"/><path class="zc_h-6bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-pen-filled" /></template>
