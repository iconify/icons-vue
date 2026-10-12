<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yismpnbbv.css';
import '../../css/t/t3kg4fp0h.css';
import '../../css/z/zc_h-6bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yismpnbbv"/><path class="t3kg4fp0h"/><path class="zc_h-6bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-plus-filled" /></template>
