<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am1po-b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":0.1,"top":0.1};
const content = `<path class="am1po-b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:droplet-fill" /></template>
