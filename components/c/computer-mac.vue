<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg_zwb-4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg_zwb-4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:computer-mac" /></template>
