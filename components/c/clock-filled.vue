<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x486k7kau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x486k7kau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clock-filled" /></template>
