<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-gy4r9ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-gy4r9ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:dots-vertical-solid" /></template>
