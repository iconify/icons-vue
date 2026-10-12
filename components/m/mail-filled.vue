<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4t4bmbus.css';
import '../../css/z/zc_h-6bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4t4bmbus"/><path class="zc_h-6bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-filled" /></template>
