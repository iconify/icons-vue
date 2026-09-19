<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iud89e5vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iud89e5vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:insert-bottom-image" /></template>
