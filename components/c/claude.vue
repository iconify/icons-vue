<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf-7u0b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf-7u0b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:claude" /></template>
