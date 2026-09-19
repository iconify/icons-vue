<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1g6zcb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1g6zcb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrange-by-numbers-9-1" /></template>
