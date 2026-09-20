<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6kghzene.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="m6kghzene"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:cutpaper" /></template>
