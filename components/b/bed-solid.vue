<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8y9gvioh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8y9gvioh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bed-solid" /></template>
