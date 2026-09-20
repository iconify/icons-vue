<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v820xhboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v820xhboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-keyhole-minimalistic-unlocked-bold" /></template>
