<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixwkb7bem.css';
import '../../css/a/aie3xzkwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixwkb7bem"/><path class="aie3xzkwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-cog" /></template>
