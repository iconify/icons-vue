<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk2wribdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk2wribdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:desk-lamp-fill" /></template>
