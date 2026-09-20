<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeoarw3ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="oeoarw3ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:facebook" /></template>
