<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvvcsfsvy.css';
import '../../css/t/ttnbi3byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvvcsfsvy"/><path clip-rule="evenodd" class="ttnbi3byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:battery-quarter-outline" /></template>
