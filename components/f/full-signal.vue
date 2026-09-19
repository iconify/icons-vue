<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyc8edbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyc8edbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:full-signal" /></template>
