<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n49uhib3z.css';
import '../../css/s/siai_tb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n49uhib3z"/><path class="siai_tb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-unread-bold" /></template>
