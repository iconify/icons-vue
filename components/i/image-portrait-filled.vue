<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb_2p8blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb_2p8blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:image-portrait-filled" /></template>
