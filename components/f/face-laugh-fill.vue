<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6900q75u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6900q75u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-laugh-fill" /></template>
