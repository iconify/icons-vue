<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crkw5cbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crkw5cbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:anvil-fill" /></template>
