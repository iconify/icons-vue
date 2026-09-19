<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp7w4tb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp7w4tb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:booth-curtain-solid" /></template>
