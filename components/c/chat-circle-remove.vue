<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlf1zvq-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlf1zvq-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chat-circle-remove" /></template>
