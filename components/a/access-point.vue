<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-518gb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-518gb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:access-point" /></template>
