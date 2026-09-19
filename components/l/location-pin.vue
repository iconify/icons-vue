<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vav2w_v0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vav2w_v0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:location-pin" /></template>
