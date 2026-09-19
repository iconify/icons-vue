<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tliyki-wu.css';
import '../../css/s/s70ezsbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tliyki-wu"/><path class="s70ezsbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:image-copy" /></template>
