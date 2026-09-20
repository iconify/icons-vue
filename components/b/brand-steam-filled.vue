<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3uequbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3uequbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-steam-filled" /></template>
