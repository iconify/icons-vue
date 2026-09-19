<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olnp0rzpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olnp0rzpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-book-alt" /></template>
