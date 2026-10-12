<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvql5q15h.css';
import '../../css/v/v8spg71sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvql5q15h"/><path clip-rule="evenodd" class="v8spg71sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:compass-filled" /></template>
