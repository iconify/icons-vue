<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwb9z7q9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwb9z7q9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hourglass" /></template>
