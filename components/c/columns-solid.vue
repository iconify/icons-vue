<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itsor3ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itsor3ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:columns-solid" /></template>
