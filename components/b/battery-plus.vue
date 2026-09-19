<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2wc9qr1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2wc9qr1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:battery-plus" /></template>
