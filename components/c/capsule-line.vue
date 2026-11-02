<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/modzxhp8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="modzxhp8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:capsule-line" /></template>
