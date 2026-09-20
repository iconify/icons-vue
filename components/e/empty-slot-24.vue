<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-9-h2b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-9-h2b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:empty-slot-24" /></template>
