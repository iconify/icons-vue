<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b40_ogsqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b40_ogsqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hard-drive-x" /></template>
