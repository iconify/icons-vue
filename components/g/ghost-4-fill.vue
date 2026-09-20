<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en88-6cnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en88-6cnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ghost-4-fill" /></template>
