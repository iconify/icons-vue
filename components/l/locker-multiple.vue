<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbewg56ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbewg56ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:locker-multiple" /></template>
