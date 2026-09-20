<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5tuxwbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="j5tuxwbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:image-flash-2-flash-power-connect-charge-electricity-lightning" /></template>
