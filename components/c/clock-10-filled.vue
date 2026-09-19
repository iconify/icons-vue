<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqc-ryket.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqc-ryket"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clock-10-filled" /></template>
