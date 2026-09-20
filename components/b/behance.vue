<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on68ukbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="on68ukbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:behance" /></template>
