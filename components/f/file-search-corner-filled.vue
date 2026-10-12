<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbg283bvc.css';
import '../../css/z/z8ho9sb_d.css';
import '../../css/y/yyu6w0k1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbg283bvc"/><path clip-rule="evenodd" class="z8ho9sb_d"/><path class="yyu6w0k1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-search-corner-filled" /></template>
