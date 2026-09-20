<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjo0hbcte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjo0hbcte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-watch-cog" /></template>
