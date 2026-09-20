<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4w9i_p-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4w9i_p-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bucket-outline" /></template>
