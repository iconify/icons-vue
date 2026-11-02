<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx9dn2b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx9dn2b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hemisphere-fill" /></template>
