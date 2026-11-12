<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3m4_fb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3m4_fb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-bolt" /></template>
