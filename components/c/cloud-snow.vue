<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq94ovnfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq94ovnfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:cloud-snow" /></template>
