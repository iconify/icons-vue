<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7s1monoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7s1monoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:jsx-02" /></template>
