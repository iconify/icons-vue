<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvxdh9bth.css';
import '../../css/h/hejbqv3cp.css';
import '../../css/p/p_2wznb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvxdh9bth"/><path class="hejbqv3cp"/><path clip-rule="evenodd" class="p_2wznb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-horizontal-bold" /></template>
