<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2-v6rp2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2-v6rp2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-d-small" /></template>
