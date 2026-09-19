<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzs1ir2gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzs1ir2gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chopsticks" /></template>
