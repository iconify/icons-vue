<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if8ou1ogq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="if8ou1ogq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:file-medical-alt-solid" /></template>
