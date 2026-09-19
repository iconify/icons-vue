<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv65rtutk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv65rtutk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:bell-off-outline" /></template>
