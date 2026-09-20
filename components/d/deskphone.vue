<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veahmxb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veahmxb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:deskphone" /></template>
