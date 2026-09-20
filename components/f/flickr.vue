<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdg-5zbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdg-5zbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flickr" /></template>
