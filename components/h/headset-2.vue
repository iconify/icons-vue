<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goiwr4gbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="goiwr4gbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headset-2" /></template>
