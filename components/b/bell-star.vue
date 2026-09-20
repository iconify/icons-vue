<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htpn1ob9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htpn1ob9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-star" /></template>
