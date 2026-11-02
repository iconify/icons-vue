<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxrdz0qlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxrdz0qlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-cny-2-fill" /></template>
