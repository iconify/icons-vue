<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rccdzuh8z.css';
import '../../css/d/du-r1xbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rccdzuh8z"/><path class="du-r1xbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:alarm-clock-minus-filled" /></template>
