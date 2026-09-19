<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqlcj6blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqlcj6blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:airport-02" /></template>
