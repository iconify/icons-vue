<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbzkg2bkw.css';
import '../../css/e/e_29zdb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbzkg2bkw"/><path class="e_29zdb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-minimalistic-bold" /></template>
