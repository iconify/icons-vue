<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szyk69b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szyk69b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heading-05" /></template>
