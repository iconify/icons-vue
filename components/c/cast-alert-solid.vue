<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g748p1bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g748p1bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cast-alert-solid" /></template>
