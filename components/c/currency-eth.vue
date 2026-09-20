<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayjea6ayf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayjea6ayf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:currency-eth" /></template>
