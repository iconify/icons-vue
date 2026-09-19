<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os_axgurn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os_axgurn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bell-slash" /></template>
