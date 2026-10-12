<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifilj8bay.css';
import '../../css/v/vw71kgb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifilj8bay"/><path clip-rule="evenodd" class="vw71kgb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-russian-ruble-filled" /></template>
