<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn02wb0-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn02wb0-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:inbox-filled" /></template>
