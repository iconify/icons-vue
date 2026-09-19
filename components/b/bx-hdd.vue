<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge_g-ku2w.css';
import '../../css/l/lzqod34yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge_g-ku2w"/><path class="lzqod34yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-hdd" /></template>
