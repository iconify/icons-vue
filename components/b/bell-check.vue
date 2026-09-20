<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw4_wyw5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw4_wyw5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bell-check" /></template>
