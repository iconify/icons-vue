<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4zsyabzx.css';
import '../../css/a/alear2y7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b4zsyabzx"/><path class="alear2y7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:business-sharp" /></template>
