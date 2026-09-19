<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezlu90ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezlu90ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:google-fill" /></template>
