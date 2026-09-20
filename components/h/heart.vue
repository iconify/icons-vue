<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf3pscb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="rf3pscb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:heart" /></template>
