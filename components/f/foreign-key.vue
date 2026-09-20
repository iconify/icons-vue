<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rra6siptg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rra6siptg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:foreign-key" /></template>
