<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0mkieb9c.css';
import '../../css/f/fccyhtt-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0mkieb9c"/><path class="fccyhtt-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bell-off-filled" /></template>
