<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0jc9qlwi.css';
import '../../css/w/wvvzy0eks.css';
import '../../css/k/kzrznpbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0jc9qlwi"/><path clip-rule="evenodd" class="wvvzy0eks"/><path clip-rule="evenodd" class="kzrznpbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-quote-bold-duotone" /></template>
