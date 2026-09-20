<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nygylfb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nygylfb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-vertical-align-bottom" /></template>
