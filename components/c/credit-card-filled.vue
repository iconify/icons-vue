<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzub7q6ne.css';
import '../../css/j/jtfx71bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lzub7q6ne"/><path class="jtfx71bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:credit-card-filled" /></template>
