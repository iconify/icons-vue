<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqqjysb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqqjysb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:bin-1" /></template>
