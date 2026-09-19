<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tue_7dbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tue_7dbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:laptop-phone-sync" /></template>
