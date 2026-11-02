<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbmndob-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbmndob-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heart-hand-fill" /></template>
