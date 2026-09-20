<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x24ss0jya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x24ss0jya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:luggage-deposit-line" /></template>
