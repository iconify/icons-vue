<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x71qnn2ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x71qnn2ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-z-filled" /></template>
