<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wagc5n8vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wagc5n8vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-meet" /></template>
