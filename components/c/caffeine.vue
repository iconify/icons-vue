<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubeai9twx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubeai9twx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:caffeine" /></template>
