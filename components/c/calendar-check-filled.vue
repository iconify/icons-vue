<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyykyh0ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tyykyh0ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:calendar-check-filled" /></template>
