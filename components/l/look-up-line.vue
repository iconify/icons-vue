<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri43c8k7n.css';
import '../../css/z/z2f80nbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri43c8k7n"/><path class="z2f80nbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:look-up-line" /></template>
