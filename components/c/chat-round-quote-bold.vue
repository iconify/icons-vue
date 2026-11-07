<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4b_ewb5v.css';
import '../../css/l/llk64db4t.css';
import '../../css/t/t000zacqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4b_ewb5v"/><path class="llk64db4t"/><path clip-rule="evenodd" class="t000zacqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-quote-bold" /></template>
