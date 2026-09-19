<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukw4jy4tx.css';
import '../../css/s/sgoebkv5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukw4jy4tx"/><path class="sgoebkv5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-right-square-half-filled" /></template>
