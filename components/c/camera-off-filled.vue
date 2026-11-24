<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh6j3gbjg.css';
import '../../css/o/oed997bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uh6j3gbjg"/><path class="oed997bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:camera-off-filled" /></template>
