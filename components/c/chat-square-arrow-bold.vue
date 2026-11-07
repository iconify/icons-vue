<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjp174btb.css';
import '../../css/f/fhnwp1bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjp174btb"/><path class="fhnwp1bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-arrow-bold" /></template>
