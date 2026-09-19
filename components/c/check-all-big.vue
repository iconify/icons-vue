<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saof0971v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saof0971v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:check-all-big" /></template>
