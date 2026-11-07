<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0jc9qlwi.css';
import '../../css/j/j08f0b1fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0jc9qlwi"/><path class="j08f0b1fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-add-bold-duotone" /></template>
