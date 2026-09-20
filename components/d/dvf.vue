<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy5h9y4sa.css';
import '../../css/n/nzkrizz9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy5h9y4sa"/><path clip-rule="evenodd" class="nzkrizz9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dvf" /></template>
