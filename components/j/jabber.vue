<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpgpy7-6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpgpy7-6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jabber" /></template>
