<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4inzjyce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="v4inzjyce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:charging-station" /></template>
