<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a41c0cirg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a41c0cirg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:escalator-descend" /></template>
