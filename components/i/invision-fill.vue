<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0kcrkbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0kcrkbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:invision-fill" /></template>
