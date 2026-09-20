<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwekcm-al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwekcm-al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:google-drive" /></template>
