<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu279i0ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu279i0ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:blocks" /></template>
