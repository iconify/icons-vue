<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsfz5syxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsfz5syxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:apple-ipad-pro" /></template>
