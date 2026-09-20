<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe9q2s79t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe9q2s79t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:http-delete" /></template>
