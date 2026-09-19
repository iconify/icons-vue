<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h98w36btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h98w36btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-right-circle-filled" /></template>
