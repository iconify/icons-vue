<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5gfqkb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5gfqkb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:eye-off" /></template>
