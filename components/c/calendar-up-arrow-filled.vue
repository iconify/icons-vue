<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2tt35wje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2tt35wje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calendar-up-arrow-filled" /></template>
