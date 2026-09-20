<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovnuc44id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovnuc44id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:jenkins" /></template>
