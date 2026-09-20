<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxz4mvbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxz4mvbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-my-business" /></template>
