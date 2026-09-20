<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brj23qz8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brj23qz8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up2-filled" /></template>
