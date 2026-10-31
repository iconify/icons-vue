<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg5mpc1ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lg5mpc1ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:checklist-boxes-solid" /></template>
