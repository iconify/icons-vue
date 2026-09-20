<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnk5bq8ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnk5bq8ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bbc" /></template>
