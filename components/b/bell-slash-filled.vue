<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apy5tabgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apy5tabgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bell-slash-filled" /></template>
