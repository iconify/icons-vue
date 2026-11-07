<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deahru6an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="deahru6an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:battery-charging-solid" /></template>
