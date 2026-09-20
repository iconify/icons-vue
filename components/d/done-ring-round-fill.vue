<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb8drvbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gb8drvbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:done-ring-round-fill" /></template>
