<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp9pt-bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wp9pt-bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:adobe-animate-filled" /></template>
