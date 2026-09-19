<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2200h6_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2200h6_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:check" /></template>
