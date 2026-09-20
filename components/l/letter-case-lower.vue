<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7w5hdmay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7w5hdmay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-case-lower" /></template>
