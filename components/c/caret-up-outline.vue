<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if8gn2bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if8gn2bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:caret-up-outline" /></template>
