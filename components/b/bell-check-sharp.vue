<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3p8yx2tq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3p8yx2tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-check-sharp" /></template>
