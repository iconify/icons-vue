<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq588tbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq588tbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:film-roll-alt-filled" /></template>
