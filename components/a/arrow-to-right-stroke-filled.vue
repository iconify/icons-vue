<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghv_czu6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghv_czu6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-to-right-stroke-filled" /></template>
