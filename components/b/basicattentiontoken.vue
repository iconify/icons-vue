<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd-qr9bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd-qr9bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:basicattentiontoken" /></template>
