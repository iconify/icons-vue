<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b21cvhnzr.css';
import '../../css/e/eqmcswb4q.css';
import '../../css/y/yyu6w0k1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b21cvhnzr"/><path class="eqmcswb4q"/><path class="yyu6w0k1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-type-corner-filled" /></template>
