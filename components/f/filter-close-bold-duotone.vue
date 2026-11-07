<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr3dwwbcg.css';
import '../../css/k/ki68ofbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr3dwwbcg"/><path class="ki68ofbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:filter-close-bold-duotone" /></template>
