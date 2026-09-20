<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-ekwybmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v-ekwybmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:directus" /></template>
