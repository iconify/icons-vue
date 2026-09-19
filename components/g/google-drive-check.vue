<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-a17nn7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-a17nn7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:google-drive-check" /></template>
