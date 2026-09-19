<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9dq7377a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9dq7377a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:location-pin-cancel-filled" /></template>
