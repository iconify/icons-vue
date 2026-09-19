<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab4ppporb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab4ppporb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lock-keyhole-open" /></template>
