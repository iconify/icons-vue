<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozxylewza.css';
import '../../css/z/ztl9t8bet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozxylewza"/><path clip-rule="evenodd" class="ztl9t8bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-gauge-filled" /></template>
