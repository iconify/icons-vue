<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md1w59b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md1w59b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ghost-filled" /></template>
