<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcw6cxbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcw6cxbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:location-remove-outline" /></template>
