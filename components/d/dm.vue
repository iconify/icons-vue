<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ved9jbbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ved9jbbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dm" /></template>
