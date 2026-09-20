<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeroz3p3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xeroz3p3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-rectangle-down-2-bold" /></template>
