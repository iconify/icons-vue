<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk7c0-brn.css';
import '../../css/b/bcoesb68t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk7c0-brn"/><path class="bcoesb68t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cog-hand-give-1-bold" /></template>
