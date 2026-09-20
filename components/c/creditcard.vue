<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2ltjr0sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h2ltjr0sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:creditcard" /></template>
