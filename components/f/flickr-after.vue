<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7mo3xirp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="c7mo3xirp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flickr-after" /></template>
