<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea7tfxbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea7tfxbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:faucet-outline" /></template>
