<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gana1fb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gana1fb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fireplace-solid" /></template>
