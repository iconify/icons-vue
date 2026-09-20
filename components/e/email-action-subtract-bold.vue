<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6cqwsbin.css';
import '../../css/b/bfi2tqb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6cqwsbin"/><path class="bfi2tqb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:email-action-subtract-bold" /></template>
