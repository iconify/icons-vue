<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knyq6nbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knyq6nbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lock4" /></template>
