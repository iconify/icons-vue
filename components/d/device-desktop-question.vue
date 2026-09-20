<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vesmpot6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vesmpot6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-desktop-question" /></template>
