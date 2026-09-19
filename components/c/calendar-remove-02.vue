<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v19_6476u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v19_6476u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calendar-remove-02" /></template>
