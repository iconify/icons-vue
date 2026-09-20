<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp31mgdgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mp31mgdgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:black-hole-2-outline" /></template>
