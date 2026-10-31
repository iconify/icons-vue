<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i461mdo7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i461mdo7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cow-fill-round" /></template>
