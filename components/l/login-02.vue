<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6xcsc10d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6xcsc10d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:login-02" /></template>
