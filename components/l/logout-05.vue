<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze52d2b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze52d2b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:logout-05" /></template>
