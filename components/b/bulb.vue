<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tezbxfici.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tezbxfici"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:bulb" /></template>
