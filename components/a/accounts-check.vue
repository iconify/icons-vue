<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt0oxtb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt0oxtb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:accounts-check" /></template>
