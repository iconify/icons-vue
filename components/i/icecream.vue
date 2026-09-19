<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm8xpob-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm8xpob-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:icecream" /></template>
