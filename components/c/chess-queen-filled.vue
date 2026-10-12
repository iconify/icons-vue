<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grrye6bcq.css';
import '../../css/k/k2cjj6b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grrye6bcq"/><path clip-rule="evenodd" class="k2cjj6b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chess-queen-filled" /></template>
