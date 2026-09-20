<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm28-rp8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm28-rp8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bugsnag" /></template>
