<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjo6nn7py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjo6nn7py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:luggage-fill" /></template>
