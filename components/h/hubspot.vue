<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7s5uktrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7s5uktrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hubspot" /></template>
