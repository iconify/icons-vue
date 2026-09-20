<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygfg23b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygfg23b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-giftcard" /></template>
