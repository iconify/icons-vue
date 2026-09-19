<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7r9geb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7r9geb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:egg-yolk-filled" /></template>
