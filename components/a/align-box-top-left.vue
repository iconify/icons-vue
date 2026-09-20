<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_5eepoak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_5eepoak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-top-left" /></template>
