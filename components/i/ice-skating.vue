<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_2joxw7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_2joxw7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ice-skating" /></template>
