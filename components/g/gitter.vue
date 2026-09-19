<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ighmcy0wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ighmcy0wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:gitter" /></template>
