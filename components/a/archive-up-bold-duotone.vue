<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6p8skb6u.css';
import '../../css/i/i3l80h-5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6p8skb6u"/><path class="i3l80h-5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-up-bold-duotone" /></template>
