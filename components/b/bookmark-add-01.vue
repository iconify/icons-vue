<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eadr-pbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eadr-pbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookmark-add-01" /></template>
