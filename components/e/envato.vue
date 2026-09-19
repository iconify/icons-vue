<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp28tacvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp28tacvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:envato" /></template>
