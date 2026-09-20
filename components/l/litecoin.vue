<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exlfeob-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exlfeob-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:litecoin" /></template>
