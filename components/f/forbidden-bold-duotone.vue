<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-lbvibdh.css';
import '../../css/i/i-d-6-4rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-lbvibdh"/><path class="i-d-6-4rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forbidden-bold-duotone" /></template>
