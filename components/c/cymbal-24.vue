<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceyuqobfb.css';
import '../../css/l/lboxqc-ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ceyuqobfb"/><path clip-rule="evenodd" class="lboxqc-ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cymbal-24" /></template>
