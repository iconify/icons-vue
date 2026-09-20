<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afmg7javi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afmg7javi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-visa" /></template>
