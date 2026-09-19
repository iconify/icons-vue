<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_vcud3rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_vcud3rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dice-5-filled" /></template>
