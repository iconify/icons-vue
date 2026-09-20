<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm7p5zbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm7p5zbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:biohazard-filled" /></template>
