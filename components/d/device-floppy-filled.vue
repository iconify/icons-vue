<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs5gx7_kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs5gx7_kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-floppy-filled" /></template>
