<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_pgp3iqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_pgp3iqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-euro-2-fill" /></template>
