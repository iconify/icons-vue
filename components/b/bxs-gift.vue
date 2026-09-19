<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyji96b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyji96b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-gift" /></template>
