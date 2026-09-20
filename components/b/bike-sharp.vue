<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eya_kzb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eya_kzb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bike-sharp" /></template>
